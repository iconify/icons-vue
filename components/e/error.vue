<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6-rj3xvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h6-rj3xvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:error" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hftt3ghvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hftt3ghvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:corner-up-right" /></template>

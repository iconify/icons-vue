<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uds0ssrod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uds0ssrod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:format-left" /></template>

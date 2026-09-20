<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxyz2h5nj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hxyz2h5nj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:certificate-2-fill" /></template>

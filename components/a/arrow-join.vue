<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmsox0bhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cmsox0bhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:arrow-join" /></template>

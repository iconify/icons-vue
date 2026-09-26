<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zp4ubxbuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zp4ubxbuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:letters" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz_kf-bir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wz_kf-bir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:liver" /></template>

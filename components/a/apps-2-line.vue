<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kz15if_zj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kz15if_zj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:apps-2-line" /></template>

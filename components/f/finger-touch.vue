<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wuhjp4b3q.css';
import '../../css/s/sx7umwbzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wuhjp4b3q"/><path class="sx7umwbzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:finger-touch" /></template>

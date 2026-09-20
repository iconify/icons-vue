<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdr35o1ib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vdr35o1ib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:father-christmas-fill" /></template>

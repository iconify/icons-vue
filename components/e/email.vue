<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ud69zyb_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ud69zyb_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mono-icons:email" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eck_ywbvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eck_ywbvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-drop-right-fill" /></template>

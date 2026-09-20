<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkj_rzrox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bkj_rzrox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:do-not-disturb-alt" /></template>

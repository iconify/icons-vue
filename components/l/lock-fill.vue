<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fs45_bcgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fs45_bcgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:lock-fill" /></template>

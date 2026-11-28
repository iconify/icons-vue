<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_wxdnm2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_wxdnm2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:antenna-solid" /></template>

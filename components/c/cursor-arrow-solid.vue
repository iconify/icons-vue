<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dl_zhm2ww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dl_zhm2ww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:cursor-arrow-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_8-s3nwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_8-s3nwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:inbox-gloss" /></template>

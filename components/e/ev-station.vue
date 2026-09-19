<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z74of7s3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z74of7s3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:ev-station" /></template>

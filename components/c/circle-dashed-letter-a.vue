<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz7zggb_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wz7zggb_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-dashed-letter-a" /></template>

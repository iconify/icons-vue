<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxq7scbii.css';
import '../../css/v/v2qz0z9zp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxq7scbii"/><path class="v2qz0z9zp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-file-jpg" /></template>

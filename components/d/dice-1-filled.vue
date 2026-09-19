<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhpu1ys3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nhpu1ys3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dice-1-filled" /></template>

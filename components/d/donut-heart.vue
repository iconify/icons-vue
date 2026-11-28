<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1wiewb_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b1wiewb_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:donut-heart" /></template>

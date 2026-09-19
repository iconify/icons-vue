<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtdd95ihe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mtdd95ihe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:gift-outline" /></template>

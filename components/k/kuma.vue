<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_5-j-2ad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_5-j-2ad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:kuma" /></template>

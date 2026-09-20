<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kk8ro-scp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kk8ro-scp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:appgallery" /></template>

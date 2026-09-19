<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-e8jibpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":500,"height":512};
const content = `<path class="n-e8jibpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:bazaar" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqv0ml9jc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mqv0ml9jc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:gradle" /></template>

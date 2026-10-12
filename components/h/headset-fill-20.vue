<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hs_dfacjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hs_dfacjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:headset-fill-20" /></template>

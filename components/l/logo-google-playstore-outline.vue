<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cw26yhbkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cw26yhbkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:logo-google-playstore-outline" /></template>

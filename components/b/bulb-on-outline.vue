<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sj1g08qrn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="sj1g08qrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:bulb-on-outline" /></template>

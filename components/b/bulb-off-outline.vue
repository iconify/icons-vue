<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/noi8_7lma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="noi8_7lma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:bulb-off-outline" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l704x-bey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":440,"height":512};
const content = `<path class="l704x-bey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:cuttlefish" /></template>

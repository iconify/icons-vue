<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rikd12bmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rikd12bmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:location-up" /></template>

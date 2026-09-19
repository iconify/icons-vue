<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/si7_7aceq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="si7_7aceq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:galactic-republic" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oviyegb7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":332,"height":512};
const content = `<path class="oviyegb7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:cloudsmith" /></template>

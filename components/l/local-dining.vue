<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usoukvb3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":408,"height":392};
const content = `<path class="usoukvb3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:local-dining" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojps68ppa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ojps68ppa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:align-center-vertical-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_3jo0xpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="e_3jo0xpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:flag-checkered" /></template>

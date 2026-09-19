<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etbrrzvpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="etbrrzvpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:bridge-water" /></template>

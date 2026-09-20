<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dpmo8pb3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="dpmo8pb3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ivy-framework" /></template>

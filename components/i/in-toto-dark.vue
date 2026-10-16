<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0d7-ntjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":366.08,"height":298.83,"left":-3.29,"top":29.96};
const content = `<path class="z0d7-ntjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:in-toto-dark" /></template>

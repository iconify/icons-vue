<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m66efibep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":16};
const content = `<path class="m66efibep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:gift" /></template>

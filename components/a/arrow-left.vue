<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smecvub7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":10,"height":16};
const content = `<path class="smecvub7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:arrow-left" /></template>

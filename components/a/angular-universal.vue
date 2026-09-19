<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnw5ewbkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rnw5ewbkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:angular-universal" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tuf02xbln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tuf02xbln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:cc-amex" /></template>

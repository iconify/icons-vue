<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7k-5-n4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="c7k-5-n4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:clipboard-check-solid" /></template>

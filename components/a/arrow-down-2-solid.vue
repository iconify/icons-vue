<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9375ab5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="n9375ab5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:arrow-down-2-solid" /></template>

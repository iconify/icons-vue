<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egk1a_o_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="egk1a_o_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:browser-remove" /></template>

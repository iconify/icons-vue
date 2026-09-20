<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkxdb4x_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fkxdb4x_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:crown-solid" /></template>

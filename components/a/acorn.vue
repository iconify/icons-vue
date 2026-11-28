<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apa-j2nit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="apa-j2nit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:acorn" /></template>

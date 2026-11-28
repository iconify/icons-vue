<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2n051b2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2n051b2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:file-code-plus" /></template>

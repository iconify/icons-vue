<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqrfzhb5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fqrfzhb5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:file-text" /></template>

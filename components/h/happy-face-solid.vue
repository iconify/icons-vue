<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbyw4pyrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jbyw4pyrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:happy-face-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cb-_2cc6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cb-_2cc6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:kos" /></template>

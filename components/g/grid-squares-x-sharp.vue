<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bf6zq1beg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bf6zq1beg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:grid-squares-x-sharp" /></template>

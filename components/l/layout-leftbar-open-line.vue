<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c52fk4sax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c52fk4sax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-leftbar-open-line" /></template>

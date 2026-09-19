<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilsrssbjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":717,"height":698};
const content = `<path class="ilsrssbjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:laugh" /></template>

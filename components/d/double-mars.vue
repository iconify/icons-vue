<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj8xsmbnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fj8xsmbnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:double-mars" /></template>

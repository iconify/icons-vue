<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0a6sbcax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="e0a6sbcax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:bbq-11" /></template>

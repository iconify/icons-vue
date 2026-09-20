<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1zhb0bqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="c1zhb0bqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:library-11" /></template>

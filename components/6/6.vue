<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jk5kzdb7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="jk5kzdb7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:6" /></template>

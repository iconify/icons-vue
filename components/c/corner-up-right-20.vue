<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6i7h5b1b.css';
import '../../css/a/a98cjoanz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n6i7h5b1b"/><path class="a98cjoanz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:corner-up-right-20" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7cc2_5lo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="c7cc2_5lo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:fly" /></template>

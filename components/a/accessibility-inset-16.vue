<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ev6n-jcqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ev6n-jcqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:accessibility-inset-16" /></template>

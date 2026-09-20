<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfslq-b4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cfslq-b4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:dot-16" /></template>

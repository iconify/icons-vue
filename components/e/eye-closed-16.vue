<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/woi1m74fw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="woi1m74fw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:eye-closed-16" /></template>

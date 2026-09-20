<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htnf9rifb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":6,"height":16};
const content = `<path class="htnf9rifb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:arrow-small-down" /></template>

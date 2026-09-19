<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to3farb2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":768};
const content = `<path class="to3farb2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:fish" /></template>

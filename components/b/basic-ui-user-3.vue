<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/it10i7brj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="it10i7brj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:basic-ui-user-3" /></template>

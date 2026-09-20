<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4v6-fb8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="c4v6-fb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:customer-support-1" /></template>

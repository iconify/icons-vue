<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npth3jbkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="npth3jbkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:entrance-alt1" /></template>

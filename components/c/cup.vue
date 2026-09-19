<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8bsvibhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a8bsvibhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:cup" /></template>

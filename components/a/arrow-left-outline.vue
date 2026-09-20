<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyvsns5gv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cyvsns5gv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:arrow-left-outline" /></template>

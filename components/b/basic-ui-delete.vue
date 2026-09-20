<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nc0wvrbrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nc0wvrbrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:basic-ui-delete" /></template>

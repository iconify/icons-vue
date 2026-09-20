<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gl9y0jbvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gl9y0jbvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:arrowheads-down-chevron" /></template>

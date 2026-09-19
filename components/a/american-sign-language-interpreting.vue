<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlnzerbth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2304,"height":1792};
const content = `<path class="xlnzerbth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:american-sign-language-interpreting" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-tx9_o5y.css';
import '../../css/z/zi9a-zbwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h-tx9_o5y"/><path class="zi9a-zbwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:download-16" /></template>

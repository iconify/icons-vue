<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3imm0oib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b3imm0oib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:file-16" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3t8i6bmf.css';
import '../../css/a/aa-24kbsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="x3t8i6bmf"/><path class="aa-24kbsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:basic-ui-unlink" /></template>

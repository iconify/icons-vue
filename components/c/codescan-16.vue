<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lrkvb8gxl.css';
import '../../css/p/pk3sogrrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lrkvb8gxl"/><path class="pk3sogrrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:codescan-16" /></template>

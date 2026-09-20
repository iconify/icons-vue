<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tr368eb4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tr368eb4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:apps-outline" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5oe7jbim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v5oe7jbim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:file-doc-outline" /></template>

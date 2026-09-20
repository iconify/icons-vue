<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1a67jbsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="v1a67jbsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:folder-filled" /></template>

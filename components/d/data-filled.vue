<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jje7dnb3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jje7dnb3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:data-filled" /></template>

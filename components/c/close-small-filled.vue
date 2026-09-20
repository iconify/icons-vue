<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4li2q-5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="j4li2q-5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:close-small-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezm5o3bwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ezm5o3bwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:add-one-filled" /></template>

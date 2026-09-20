<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_8m4dn5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="r_8m4dn5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:basic-ui-add-2" /></template>

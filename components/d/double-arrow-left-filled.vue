<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bo9fgqb0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bo9fgqb0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:double-arrow-left-filled" /></template>

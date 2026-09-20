<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmr2wt9_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zmr2wt9_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:input-box-remix" /></template>

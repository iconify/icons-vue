<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bl0rpkbli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":717,"height":717};
const content = `<path class="bl0rpkbli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:help" /></template>

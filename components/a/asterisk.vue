<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r19nw1ghx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="r19nw1ghx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:asterisk" /></template>

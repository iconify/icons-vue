<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oox-7jbzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="oox-7jbzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:asterisk" /></template>

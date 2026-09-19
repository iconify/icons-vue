<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvqwzbcbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":717,"height":669};
const content = `<path class="yvqwzbcbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:game" /></template>

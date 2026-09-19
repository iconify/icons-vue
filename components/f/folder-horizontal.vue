<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwlcm5sli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="mwlcm5sli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:folder-horizontal" /></template>

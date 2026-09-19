<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orxitfbis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":255,"height":754};
const content = `<path class="orxitfbis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:f" /></template>

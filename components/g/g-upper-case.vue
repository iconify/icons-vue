<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgydwwb3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":795,"height":776};
const content = `<path class="lgydwwb3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:g-upper-case" /></template>

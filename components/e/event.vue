<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8efn-fzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":960};
const content = `<path class="h8efn-fzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:event" /></template>

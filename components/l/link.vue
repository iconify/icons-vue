<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbxpb3brk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nbxpb3brk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:link" /></template>

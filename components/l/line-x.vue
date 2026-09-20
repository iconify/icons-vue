<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9ac-_bck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="m9ac-_bck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:line-x" /></template>

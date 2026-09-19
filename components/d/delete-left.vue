<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0e07wo_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="d0e07wo_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:delete-left" /></template>

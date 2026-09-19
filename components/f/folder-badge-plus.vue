<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyfe-73fe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="vyfe-73fe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:folder-badge-plus" /></template>

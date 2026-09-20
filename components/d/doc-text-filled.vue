<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1eh47evz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m1eh47evz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:doc-text-filled" /></template>

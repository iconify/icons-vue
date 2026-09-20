<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkbx1vb9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bkbx1vb9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:graph-filled" /></template>

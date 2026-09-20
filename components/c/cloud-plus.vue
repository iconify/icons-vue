<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3vt6vbuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u3vt6vbuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:cloud-plus" /></template>

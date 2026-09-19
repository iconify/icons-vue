<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_pon7jss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c_pon7jss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:disappointed-face-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oijg09-qq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oijg09-qq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:list-ordered" /></template>

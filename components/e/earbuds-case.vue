<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o02f8kibj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o02f8kibj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:earbuds-case" /></template>

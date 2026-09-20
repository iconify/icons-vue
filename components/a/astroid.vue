<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6u9v2bvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u6u9v2bvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:astroid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asso8q0pr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="asso8q0pr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-right-4-square-fill" /></template>

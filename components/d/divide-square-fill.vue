<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ua200fb8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ua200fb8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:divide-square-fill" /></template>

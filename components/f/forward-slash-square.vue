<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6jwd8c5d.css';
import '../../css/j/jor-usn7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u6jwd8c5d"/><path class="jor-usn7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:forward-slash-square" /></template>

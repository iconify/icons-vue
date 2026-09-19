<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/et7pcw8op.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="et7pcw8op"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:caret-big-down" /></template>

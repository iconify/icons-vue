<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgh5n0t4o.css';
import '../../css/j/jor-usn7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fgh5n0t4o"/><path class="jor-usn7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-down-right-stroke-square" /></template>

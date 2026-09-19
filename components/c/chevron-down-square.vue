<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c84qon53b.css';
import '../../css/j/jor-usn7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c84qon53b"/><path class="jor-usn7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:chevron-down-square" /></template>

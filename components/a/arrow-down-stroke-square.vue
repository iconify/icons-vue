<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_t5xxb1r.css';
import '../../css/j/jor-usn7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_t5xxb1r"/><path class="jor-usn7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-down-stroke-square" /></template>

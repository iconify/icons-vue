<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vh6x2fi-r.css';
import '../../css/j/jor-usn7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vh6x2fi-r"/><path class="jor-usn7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-up-stroke-square" /></template>

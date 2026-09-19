<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxxxs129g.css';
import '../../css/j/jor-usn7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kxxxs129g"/><path class="jor-usn7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-up-left-square" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7wfo1l2j.css';
import '../../css/h/hpwczr9zj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="g7wfo1l2j"/><path class="hpwczr9zj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:commonwealth-of-nations" /></template>

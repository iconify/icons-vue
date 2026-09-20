<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/foufpwbhx.css';
import '../../css/i/itcwtlbql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="foufpwbhx"/><path class="itcwtlbql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:download-light" /></template>

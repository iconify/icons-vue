<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2o79t15y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2o79t15y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:database-off" /></template>

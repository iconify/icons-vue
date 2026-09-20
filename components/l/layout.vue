<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfrir8xvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hfrir8xvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:layout" /></template>

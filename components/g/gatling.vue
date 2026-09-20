<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nja97d98y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nja97d98y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:gatling" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tq4cvr6jb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tq4cvr6jb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:dumbbell" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uuaegz5hh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uuaegz5hh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:armchair" /></template>

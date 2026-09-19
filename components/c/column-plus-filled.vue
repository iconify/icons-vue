<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdym82bfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hdym82bfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:column-plus-filled" /></template>

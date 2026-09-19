<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/an3el_c8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="an3el_c8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:large-orange-diamond" /></template>

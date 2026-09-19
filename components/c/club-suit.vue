<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gicopp7ns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gicopp7ns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:club-suit" /></template>

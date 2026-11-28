<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhae88n8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhae88n8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:bird-heart" /></template>

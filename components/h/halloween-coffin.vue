<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikj4i246g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ikj4i246g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:halloween-coffin" /></template>

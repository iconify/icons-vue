<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln6t4lble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ln6t4lble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:hacker" /></template>

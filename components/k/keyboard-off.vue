<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxc5sxbvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rxc5sxbvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:keyboard-off" /></template>

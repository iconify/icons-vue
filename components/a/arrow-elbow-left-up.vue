<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8pjo6bak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c8pjo6bak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:arrow-elbow-left-up" /></template>

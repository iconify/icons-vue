<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7hn0-rgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v7hn0-rgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:comment-alt-search" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqeop9uzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqeop9uzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:chevron-right-duo" /></template>

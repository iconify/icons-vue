<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fk0626bjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fk0626bjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:folder-off" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfewk7bue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gfewk7bue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:gauge" /></template>

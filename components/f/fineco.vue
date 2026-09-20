<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwllu7uxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iwllu7uxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:fineco" /></template>

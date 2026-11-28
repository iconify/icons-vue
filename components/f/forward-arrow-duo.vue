<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9xbjpe9s.css';
import '../../css/i/icurep0mw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i9xbjpe9s secondary"/><path class="icurep0mw primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:forward-arrow-duo" /></template>

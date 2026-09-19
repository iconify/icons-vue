<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffolzo65m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ffolzo65m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:format-strike" /></template>

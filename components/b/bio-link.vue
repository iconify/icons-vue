<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fsa0o9kyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fsa0o9kyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:bio-link" /></template>

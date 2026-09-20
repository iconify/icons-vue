<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abvwb5blb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="abvwb5blb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:happy-face-remix" /></template>

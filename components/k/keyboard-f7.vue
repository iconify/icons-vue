<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irk2yqbfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="irk2yqbfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:keyboard-f7" /></template>

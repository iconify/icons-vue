<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0mfz3j4c.css';
import '../../css/u/uvedyyb9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b0mfz3j4c"/><path class="uvedyyb9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-group" /></template>

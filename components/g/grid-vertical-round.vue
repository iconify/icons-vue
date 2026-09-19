<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lij1qyb8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lij1qyb8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:grid-vertical-round" /></template>

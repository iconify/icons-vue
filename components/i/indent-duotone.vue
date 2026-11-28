<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flgb0ccza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="flgb0ccza primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:indent-duotone" /></template>

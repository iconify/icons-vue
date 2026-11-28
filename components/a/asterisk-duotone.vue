<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hyglkvb0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hyglkvb0z primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:asterisk-duotone" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb56rqbrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tb56rqbrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:flag-alt-4-fill" /></template>

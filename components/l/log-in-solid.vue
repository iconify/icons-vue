<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anb2ifbdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="anb2ifbdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:log-in-solid" /></template>

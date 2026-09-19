<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i534_nb7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i534_nb7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:instance" /></template>

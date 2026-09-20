<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4787ac0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h4787ac0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:arrow-up-to-line" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t69e_jbfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t69e_jbfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:edit-pencil" /></template>

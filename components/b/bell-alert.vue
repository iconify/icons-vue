<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d64o0ob4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d64o0ob4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:bell-alert" /></template>

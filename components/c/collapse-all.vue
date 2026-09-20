<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwvj0zbvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cwvj0zbvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:collapse-all" /></template>

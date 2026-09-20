<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i59tw3b4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i59tw3b4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:gsma" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pe49jsfsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pe49jsfsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:arrow-circle-up-left-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlrbr0wwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vlrbr0wwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:keyboard-f3" /></template>

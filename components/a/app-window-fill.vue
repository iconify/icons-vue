<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/muv5wpe8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="muv5wpe8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:app-window-fill" /></template>

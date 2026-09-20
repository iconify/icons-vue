<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s63khdc0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s63khdc0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-cursor-fill" /></template>

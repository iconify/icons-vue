<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n878sudbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n878sudbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:dice-4-fill" /></template>

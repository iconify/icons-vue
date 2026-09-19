<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3b_oab5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="e3b_oab5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:lab-flask" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9o_cmb9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f9o_cmb9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:crown-fill" /></template>

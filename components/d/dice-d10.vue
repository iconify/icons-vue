<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc5lsvbrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vc5lsvbrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:dice-d10" /></template>

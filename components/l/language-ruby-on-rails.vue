<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ri4pj7yyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ri4pj7yyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:language-ruby-on-rails" /></template>

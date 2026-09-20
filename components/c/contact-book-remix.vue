<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jv851mbmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jv851mbmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:contact-book-remix" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkqg3otwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bkqg3otwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:language-haskell" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j408grkht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j408grkht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:braces" /></template>

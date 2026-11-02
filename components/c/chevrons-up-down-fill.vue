<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fp2ariv_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fp2ariv_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chevrons-up-down-fill" /></template>

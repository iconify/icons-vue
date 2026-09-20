<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxkqfm6nt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxkqfm6nt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:gift-fill" /></template>

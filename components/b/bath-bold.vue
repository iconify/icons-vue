<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqdha0jda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqdha0jda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bath-bold" /></template>

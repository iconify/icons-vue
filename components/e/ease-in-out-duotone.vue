<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpg0fzbjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary rpg0fzbjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:ease-in-out-duotone" /></template>

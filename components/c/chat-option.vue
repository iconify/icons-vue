<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q026oo9wp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q026oo9wp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:chat-option" /></template>

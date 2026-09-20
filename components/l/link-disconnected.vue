<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjqeuo1dk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rjqeuo1dk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:link-disconnected" /></template>

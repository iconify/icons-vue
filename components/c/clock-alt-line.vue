<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzdsy5qft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bzdsy5qft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:clock-alt-line" /></template>

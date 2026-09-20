<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-kj1jbpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-kj1jbpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:crown" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqez_59rt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fqez_59rt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flame-fill" /></template>

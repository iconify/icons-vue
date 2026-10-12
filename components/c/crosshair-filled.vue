<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7s-3o5ea.css';
import '../../css/c/cd94oju7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u7s-3o5ea"/><path clip-rule="evenodd" class="cd94oju7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:crosshair-filled" /></template>

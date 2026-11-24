<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fx6x9k59k.css';
import '../../css/z/zoxpwbb0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fx6x9k59k"/><path class="zoxpwbb0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:folder-plus-corner-filled" /></template>

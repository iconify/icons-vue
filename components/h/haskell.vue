<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftv36rb_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ftv36rb_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:haskell" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7ud-hb3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q7ud-hb3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:astroid-filled" /></template>

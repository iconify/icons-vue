<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fg1mtqeek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fg1mtqeek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:git-pull-request-draft-filled" /></template>

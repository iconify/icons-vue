<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0niglb5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c0niglb5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:elephant-face" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozg9svb1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ozg9svb1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:flame-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pw-8x5o7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pw-8x5o7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:astroid-filled" /></template>

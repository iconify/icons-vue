<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebq0opbqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ebq0opbqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:heart-filled" /></template>

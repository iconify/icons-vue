<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qams0c-7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qams0c-7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:align-vertical-justify-start-filled" /></template>

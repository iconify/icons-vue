<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ro1fyrkqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ro1fyrkqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:chevron-up-circle" /></template>

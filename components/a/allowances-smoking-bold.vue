<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fu4coba6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fu4coba6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:allowances-smoking-bold" /></template>

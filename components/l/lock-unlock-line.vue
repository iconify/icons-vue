<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9sinp6my.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q9sinp6my"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:lock-unlock-line" /></template>

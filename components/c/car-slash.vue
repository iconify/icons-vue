<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8yc3wc8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q8yc3wc8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:car-slash" /></template>

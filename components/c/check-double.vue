<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q26vg3huj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q26vg3huj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:check-double" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjwu3kbww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qjwu3kbww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:face-id-outline" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vu6mqqb7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":696,"height":1000};
const content = `<path class="vu6mqqb7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontelico:emo-surprised" /></template>

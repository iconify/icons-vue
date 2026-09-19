<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abdpe8btv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="abdpe8btv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:lightbulb" /></template>

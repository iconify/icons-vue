<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d93v-8biw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d93v-8biw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:book-minus" /></template>

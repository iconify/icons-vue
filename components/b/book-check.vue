<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyau_4blo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dyau_4blo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:book-check" /></template>

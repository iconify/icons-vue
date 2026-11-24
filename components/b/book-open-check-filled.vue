<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhxzawb3p.css';
import '../../css/f/f8paaybnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhxzawb3p"/><path class="f8paaybnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:book-open-check-filled" /></template>

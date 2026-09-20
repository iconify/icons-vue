<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbflqv4vi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zbflqv4vi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:checklist-16-solid" /></template>

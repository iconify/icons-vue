<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8rw7r2au.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="e8rw7r2au"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:briefcase-small" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6a78ihov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6a78ihov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:book-plus-sharp" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wx7lfyb5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="wx7lfyb5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:equal" /></template>

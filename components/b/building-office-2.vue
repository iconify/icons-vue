<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrb9f-tmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="vrb9f-tmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:building-office-2" /></template>

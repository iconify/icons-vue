<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-ke-cb5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="q-ke-cb5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:dots-y" /></template>

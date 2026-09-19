<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kva5axb4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kva5axb4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:bell-snooze" /></template>

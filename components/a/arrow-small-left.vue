<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihzocydtt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ihzocydtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-small-left" /></template>

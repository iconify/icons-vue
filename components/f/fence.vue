<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5qkshlib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q5qkshlib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:fence" /></template>

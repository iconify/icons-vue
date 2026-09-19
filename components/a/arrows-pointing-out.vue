<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km50ekb7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="km50ekb7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:arrows-pointing-out" /></template>

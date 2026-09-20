<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-7ndvbeb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-7ndvbeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:grid-3x3-bold" /></template>

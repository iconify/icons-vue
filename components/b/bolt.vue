<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilt4b8bzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ilt4b8bzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:bolt" /></template>

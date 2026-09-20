<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8b78u5qv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g8b78u5qv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hanger-2-outline" /></template>

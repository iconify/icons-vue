<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7j9a7h-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n7j9a7h-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:act" /></template>

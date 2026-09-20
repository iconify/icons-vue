<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgsckkp6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dgsckkp6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:glq" /></template>

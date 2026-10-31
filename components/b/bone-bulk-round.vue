<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4kl7kb8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c4kl7kb8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bone-bulk-round" /></template>

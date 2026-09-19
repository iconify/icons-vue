<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2f33912z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a2f33912z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:distribute-vertical-bottom" /></template>

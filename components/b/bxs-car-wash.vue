<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5xp2-b5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a5xp2-b5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-car-wash" /></template>

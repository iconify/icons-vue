<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eb0r9l_nb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eb0r9l_nb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-pin" /></template>

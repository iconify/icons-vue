<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjn0nvr9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hjn0nvr9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:cone-2-filled" /></template>

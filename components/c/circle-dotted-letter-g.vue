<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhlh6pjrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhlh6pjrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-dotted-letter-g" /></template>

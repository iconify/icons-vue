<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/teihqdf3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="teihqdf3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:hourglass" /></template>

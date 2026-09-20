<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ouvm6tl5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ouvm6tl5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bell-x" /></template>

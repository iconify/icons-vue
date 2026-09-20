<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7nwo27os.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h7nwo27os"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-narrow-left" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ii1xarbkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ii1xarbkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:book-4-fill" /></template>

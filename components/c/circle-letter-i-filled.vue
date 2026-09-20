<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/so1ox1b0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="so1ox1b0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-letter-i-filled" /></template>

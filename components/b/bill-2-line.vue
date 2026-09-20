<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/juhk9ubtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="juhk9ubtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bill-2-line" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-00mr7rz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-00mr7rz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-list-numbered-right-to-left" /></template>

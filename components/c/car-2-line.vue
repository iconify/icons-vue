<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9jqhvbix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w9jqhvbix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:car-2-line" /></template>

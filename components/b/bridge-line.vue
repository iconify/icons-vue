<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldwn1jb5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ldwn1jb5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bridge-line" /></template>

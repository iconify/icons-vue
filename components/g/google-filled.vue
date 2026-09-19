<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lm7hx7-he.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lm7hx7-he"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:google-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glz0wvbtt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="glz0wvbtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dna-off-line" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6hq9wb1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d6hq9wb1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:building-code" /></template>

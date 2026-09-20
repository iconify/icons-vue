<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rznhs0r4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rznhs0r4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bubble-plus" /></template>

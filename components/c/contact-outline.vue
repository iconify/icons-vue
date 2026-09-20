<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s380qsb2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="s380qsb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:contact-outline" /></template>

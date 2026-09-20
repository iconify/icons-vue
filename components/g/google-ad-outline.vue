<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6zsw8m6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="r6zsw8m6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:google-ad-outline" /></template>

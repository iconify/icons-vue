<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2555zbkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="l2555zbkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:google-outline" /></template>

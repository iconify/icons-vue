<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_unyib1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":994.95,"height":1000};
const content = `<path class="q_unyib1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="brandico:lastfm" /></template>

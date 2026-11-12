<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iaonzxg2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iaonzxg2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:anki-dark" /></template>

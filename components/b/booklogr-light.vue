<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1-othb1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s1-othb1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:booklogr-light" /></template>

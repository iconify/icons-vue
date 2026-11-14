<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtkmayb8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rtkmayb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cancel-01" /></template>

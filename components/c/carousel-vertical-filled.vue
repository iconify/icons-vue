<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9mopgb2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k9mopgb2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:carousel-vertical-filled" /></template>

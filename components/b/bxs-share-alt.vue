<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q90a30i4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q90a30i4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-share-alt" /></template>

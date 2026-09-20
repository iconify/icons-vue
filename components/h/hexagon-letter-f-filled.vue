<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1ggj4blw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k1ggj4blw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:hexagon-letter-f-filled" /></template>

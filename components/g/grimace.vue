<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/auxx8in_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="auxx8in_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:grimace" /></template>

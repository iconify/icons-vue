<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fydhr5h3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="fydhr5h3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:clipboard-list-mirrored" /></template>

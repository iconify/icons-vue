<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r63myebdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r63myebdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:bag-heart" /></template>

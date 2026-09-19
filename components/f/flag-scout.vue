<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fn85yfbuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":480,"height":512};
const content = `<path class="fn85yfbuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:flag-scout" /></template>

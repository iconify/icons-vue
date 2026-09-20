<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5oq8rb2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":10,"height":10};
const content = `<path class="r5oq8rb2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:bus-stop-10" /></template>

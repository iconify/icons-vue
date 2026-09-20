<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9pk-gb7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q9pk-gb7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fandom-dark" /></template>

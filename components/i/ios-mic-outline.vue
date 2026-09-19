<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-e9bcc3c.css';
import '../../css/d/dr9-gqbcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s-e9bcc3c"/><path class="dr9-gqbcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-mic-outline" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q53a_eb2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="q53a_eb2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="marketeq:attachment" /></template>

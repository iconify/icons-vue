<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mj_5nup2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="mj_5nup2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:emojiconfused" /></template>

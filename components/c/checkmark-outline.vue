<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2pqswazu.css';
import '../../css/w/ww4fyqbuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q2pqswazu"/><path class="ww4fyqbuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:checkmark-outline" /></template>

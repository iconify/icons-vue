<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwho4kv5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gwho4kv5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:equalizer-2" /></template>

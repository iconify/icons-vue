<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wu_5mwbvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1026};
const content = `<path class="wu_5mwbvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:lemon" /></template>

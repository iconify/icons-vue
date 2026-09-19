<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlb12tben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="vlb12tben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:bubble-left-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwdf5sbkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="iwdf5sbkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:dice-5-remix" /></template>

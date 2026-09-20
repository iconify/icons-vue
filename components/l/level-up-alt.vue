<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fokbu2brg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fokbu2brg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:level-up-alt" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9028ebbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="y9028ebbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:goforward-plus" /></template>

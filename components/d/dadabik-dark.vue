<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wj8w24brh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wj8w24brh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dadabik-dark" /></template>

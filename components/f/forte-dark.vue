<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wunxpj0up.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wunxpj0up"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:forte-dark" /></template>

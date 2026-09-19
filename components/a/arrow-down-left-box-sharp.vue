<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jn3j_6bgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="jn3j_6bgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:arrow-down-left-box-sharp" /></template>

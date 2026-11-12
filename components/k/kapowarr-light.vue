<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcmta96sd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zcmta96sd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kapowarr-light" /></template>

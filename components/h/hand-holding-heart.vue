<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r80kynbyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="r80kynbyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:hand-holding-heart" /></template>

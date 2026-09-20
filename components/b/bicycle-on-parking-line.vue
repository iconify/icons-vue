<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyoyubbjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vyoyubbjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bicycle-on-parking-line" /></template>

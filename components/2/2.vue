<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nb_0tkhsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nb_0tkhsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:2" /></template>

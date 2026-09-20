<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0k1bibib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="z0k1bibib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:fishes" /></template>

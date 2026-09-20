<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zt-nhpvlw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zt-nhpvlw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:five-minus-above-water" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oiqfbpcfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1545,"height":1544};
const content = `<path class="oiqfbpcfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:gevernova" /></template>

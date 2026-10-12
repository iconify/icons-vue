<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sut_o-gje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sut_o-gje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:heart-stroke-20" /></template>

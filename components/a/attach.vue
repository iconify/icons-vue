<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0bzdbvnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k0bzdbvnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:attach" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzt0lm2ue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="pzt0lm2ue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:discount-solid" /></template>

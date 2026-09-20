<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w048f229i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="w048f229i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:credit-card-outline" /></template>

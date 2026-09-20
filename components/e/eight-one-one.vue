<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nl6az0olz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nl6az0olz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:eight-one-one" /></template>

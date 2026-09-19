<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4kyyqbgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r4kyyqbgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:car-battery" /></template>

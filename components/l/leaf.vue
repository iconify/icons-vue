<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udufwfb0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="udufwfb0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:leaf" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/du0febchq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="du0febchq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:flag-20-solid" /></template>

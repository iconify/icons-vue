<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5bz3lbad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="s5bz3lbad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:currency-yen-16-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8mpkoifm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="o8mpkoifm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:bitcoin-solid" /></template>

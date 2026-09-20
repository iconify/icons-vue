<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tken0i2np.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="tken0i2np"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:arrow-right-down" /></template>

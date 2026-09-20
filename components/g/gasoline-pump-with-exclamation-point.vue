<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iio2e3udq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="iio2e3udq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:gasoline-pump-with-exclamation-point" /></template>

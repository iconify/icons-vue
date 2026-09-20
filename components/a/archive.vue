<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aev0f0bxv.css';
import '../../css/b/b-yzc2u7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="aev0f0bxv"/><path class="b-yzc2u7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:archive" /></template>

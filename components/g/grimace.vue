<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eod_tkbqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="eod_tkbqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:grimace" /></template>

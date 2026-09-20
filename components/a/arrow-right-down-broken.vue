<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r908o0etm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r908o0etm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-right-down-broken" /></template>

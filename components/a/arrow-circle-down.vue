<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5it68bnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x5it68bnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:arrow-circle-down" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eahow9bvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eahow9bvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:down-arrow-1" /></template>

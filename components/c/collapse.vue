<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rb8rx2b1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rb8rx2b1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:collapse" /></template>

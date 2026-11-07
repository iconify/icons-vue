<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sd7x7gmgh.css';
import '../../css/r/r_ko2hb4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sd7x7gmgh"/><path class="r_ko2hb4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:infinite-bold-duotone" /></template>

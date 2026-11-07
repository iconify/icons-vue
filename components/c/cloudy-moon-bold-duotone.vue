<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbi4wky7o.css';
import '../../css/s/sfo2tsbqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bbi4wky7o"/><path class="sfo2tsbqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cloudy-moon-bold-duotone" /></template>

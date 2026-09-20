<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lk_1fybkb.css';
import '../../css/h/hc5l59cwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lk_1fybkb"/><path class="hc5l59cwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:codespaces-24" /></template>

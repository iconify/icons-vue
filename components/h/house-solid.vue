<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_inqrbwp.css';
import '../../css/a/ad1wvybmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="r_inqrbwp"/><path class="ad1wvybmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:house-solid" /></template>

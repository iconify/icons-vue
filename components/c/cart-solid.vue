<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kw20fcbyu.css';
import '../../css/d/ds8m3ccms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kw20fcbyu"/><path clip-rule="evenodd" class="ds8m3ccms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:cart-solid" /></template>

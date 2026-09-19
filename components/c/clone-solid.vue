<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fufj9heoj.css';
import '../../css/g/g_c_o4b2g.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 fufj9heoj"/><path class="clr-i-solid clr-i-solid-path-2 g_c_o4b2g"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:clone-solid" /></template>

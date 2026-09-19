<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5pfuk6lz.css';
import '../../css/p/ps_hawo5j.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 z5pfuk6lz"/><path class="clr-i-solid clr-i-solid-path-2 ps_hawo5j"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:language-solid" /></template>

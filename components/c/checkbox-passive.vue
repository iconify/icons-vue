<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oy_iv7ssp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="oy_iv7ssp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:checkbox-passive" /></template>

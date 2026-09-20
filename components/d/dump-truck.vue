<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzjso_7pd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jzjso_7pd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:dump-truck" /></template>

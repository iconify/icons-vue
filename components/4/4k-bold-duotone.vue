<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0p-2pbst.css';
import '../../css/e/efoiiwh-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g0p-2pbst"/><path class="efoiiwh-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:4k-bold-duotone" /></template>

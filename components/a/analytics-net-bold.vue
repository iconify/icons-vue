<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpf4hcbel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jpf4hcbel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:analytics-net-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9uem0hua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k9uem0hua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bar-chart-horizontal-end-sharp" /></template>

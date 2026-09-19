<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vsdnl787g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vsdnl787g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:lifebuoy" /></template>

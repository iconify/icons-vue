<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxmthib0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yxmthib0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:battery-3-outline" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zs59dwcbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zs59dwcbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mono-icons:filter-alt" /></template>

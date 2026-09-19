<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmd0k7brn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dmd0k7brn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:fox" /></template>

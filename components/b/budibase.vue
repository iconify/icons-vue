<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lw_zlwbus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lw_zlwbus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:budibase" /></template>

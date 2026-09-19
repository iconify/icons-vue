<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpjn-lbyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tpjn-lbyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:keyboard" /></template>

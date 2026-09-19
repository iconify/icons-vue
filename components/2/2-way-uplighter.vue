<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ly-okgncv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ly-okgncv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:2-way-uplighter" /></template>

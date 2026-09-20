<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hl6g3-bfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hl6g3-bfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:ease-in-out-control-points" /></template>

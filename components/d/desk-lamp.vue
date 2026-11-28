<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzy2t0_hv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lzy2t0_hv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:desk-lamp" /></template>

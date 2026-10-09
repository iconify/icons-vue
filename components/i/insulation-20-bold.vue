<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1mcems0k.css';
import '../../css/t/t_bk3zflf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l1mcems0k"/><path class="t_bk3zflf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:insulation-20-bold" /></template>

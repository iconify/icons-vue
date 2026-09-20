<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/td8i4ib_z.css';
import '../../css/b/bxw0pccgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="td8i4ib_z"/><path class="bxw0pccgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:gauge-high-16" /></template>

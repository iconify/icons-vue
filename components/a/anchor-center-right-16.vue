<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v528_2bxm.css';
import '../../css/v/voocfbbkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v528_2bxm"/><path class="voocfbbkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:anchor-center-right-16" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zy5wuebdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zy5wuebdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:layout-dashboard-sharp" /></template>

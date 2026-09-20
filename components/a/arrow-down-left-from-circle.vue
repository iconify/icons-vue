<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trifqr1dn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="trifqr1dn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:arrow-down-left-from-circle" /></template>

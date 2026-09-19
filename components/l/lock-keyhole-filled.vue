<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lntrp4opm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lntrp4opm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:lock-keyhole-filled" /></template>

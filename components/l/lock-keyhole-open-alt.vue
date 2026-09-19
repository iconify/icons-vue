<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dv-bsibru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dv-bsibru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:lock-keyhole-open-alt" /></template>

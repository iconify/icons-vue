<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yiemwqbmv.css';
import '../../css/k/k6k1t_68c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yiemwqbmv"/><path class="k6k1t_68c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:heart-plus" /></template>

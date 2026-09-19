<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h0ugaht_w.css';
import '../../css/d/dbovvfb-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h0ugaht_w"/><path class="dbovvfb-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:air-conditioner" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sun_ywaan.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sun_ywaan"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:error-400" /></template>

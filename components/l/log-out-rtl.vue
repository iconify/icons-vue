<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbbc_v-5y.css';
import '../../css/v/vvfyzqbfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mbbc_v-5y"/><path class="vvfyzqbfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:log-out-rtl" /></template>

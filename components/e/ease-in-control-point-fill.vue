<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mp_nfnigp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mp_nfnigp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ease-in-control-point-fill" /></template>

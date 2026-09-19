<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhy12_s6e.css';
import '../../css/o/o_rxuaclz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hhy12_s6e"/><path class="o_rxuaclz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:institution-filled" /></template>

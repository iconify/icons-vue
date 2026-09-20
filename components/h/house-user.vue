<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_zb0x5py.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_zb0x5py"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:house-user" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icpnc-zav.css';
import '../../css/f/fkh-yubxj.css';
import '../../css/j/j61w4jzst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="icpnc-zav"/><path class="fkh-yubxj"/><path class="j61w4jzst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:earth-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r36e_8bxp.css';
import '../../css/m/mfr2nesuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r36e_8bxp"/><path class="mfr2nesuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:browse-off-filled" /></template>

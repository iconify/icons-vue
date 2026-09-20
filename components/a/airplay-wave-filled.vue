<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hyvvzzbvp.css';
import '../../css/m/mqf73h98a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hyvvzzbvp"/><path class="mqf73h98a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:airplay-wave-filled" /></template>

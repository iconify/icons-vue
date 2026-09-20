<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gsz_kweuc.css';
import '../../css/n/nb3whwxik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gsz_kweuc"/><path class="nb3whwxik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:gamepad-button-right-16" /></template>

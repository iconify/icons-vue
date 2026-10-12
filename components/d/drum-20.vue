<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/decyyub_r.css';
import '../../css/z/zz5z_zbiw.css';
import '../../css/d/d880qybrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="decyyub_r"/><path class="zz5z_zbiw"/><path class="d880qybrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:drum-20" /></template>

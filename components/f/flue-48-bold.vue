<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jikxxnb7a.css';
import '../../css/r/r_d_ijm8a.css';
import '../../css/d/d8xz_bcrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jikxxnb7a"/><path class="r_d_ijm8a"/><path class="d8xz_bcrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:flue-48-bold" /></template>

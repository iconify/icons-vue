<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2l7e5b5j.css';
import '../../css/z/zqt46prvm.css';
import '../../css/l/l9jgh7bvz.css';
import '../../css/s/st45emjbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k2l7e5b5j"/><path class="zqt46prvm"/><path class="l9jgh7bvz"/><path class="st45emjbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:camera-plus-48-bold" /></template>

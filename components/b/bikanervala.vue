<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bo07ssopt.css';
import '../../css/l/l19u7itse.css';
import '../../css/p/p5xn_tbck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1999.5,"height":691.5,"left":0.48,"top":4.5};
const content = `<path class="bo07ssopt"/><path class="l19u7itse"/><path class="p5xn_tbck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:bikanervala" /></template>

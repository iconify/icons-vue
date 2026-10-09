<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkestgbmb.css';
import '../../css/k/kc-33db0z.css';
import '../../css/w/wdh6v20fa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nkestgbmb"/><path class="kc-33db0z"/><path class="wdh6v20fa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydrogen-boiler-20" /></template>

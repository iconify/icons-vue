<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pi1hn-gpe.css';
import '../../css/q/qln6u-bog.css';
import '../../css/n/n02nodbdf.css';
import '../../css/o/okxkqqbnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pi1hn-gpe"/><path class="qln6u-bog"/><path class="n02nodbdf"/><path class="okxkqqbnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ev-charger-20-bold" /></template>

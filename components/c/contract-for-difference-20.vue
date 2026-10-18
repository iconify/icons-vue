<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szahujb-p.css';
import '../../css/o/ocsvobbfk.css';
import '../../css/q/qr12-ubkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="szahujb-p"/><path class="ocsvobbfk"/><path class="qr12-ubkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:contract-for-difference-20" /></template>

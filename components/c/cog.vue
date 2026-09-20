<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfv3j0v9a.css';
import '../../css/h/hbhflsb1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="qfv3j0v9a"/><path class="hbhflsb1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:cog" /></template>

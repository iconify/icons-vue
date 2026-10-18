<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ec4h7ebhn.css';
import '../../css/x/xz2t00wzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ec4h7ebhn"/><path class="xz2t00wzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:green-jobs-20" /></template>

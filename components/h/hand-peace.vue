<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qlzcbobup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qlzcbobup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:hand-peace" /></template>

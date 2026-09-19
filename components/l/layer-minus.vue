<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc9dwfbws.css';
import '../../css/h/hj974yb2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bc9dwfbws"/><path class="hj974yb2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:layer-minus" /></template>

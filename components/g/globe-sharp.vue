<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfb5d6b_i.css';
import '../../css/b/bt4w0gb_w.css';
import '../../css/g/g40sm1q7e.css';
import '../../css/y/yf66grb3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lfb5d6b_i"/><path class="bt4w0gb_w"/><path class="g40sm1q7e"/><path class="yf66grb3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:globe-sharp" /></template>

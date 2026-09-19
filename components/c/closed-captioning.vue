<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcxs3hbaw.css';
import '../../css/s/sq3z-9xqp.css';
import '../../css/y/y-e0_cb5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zcxs3hbaw"/><path class="sq3z-9xqp"/><path class="y-e0_cb5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:closed-captioning" /></template>

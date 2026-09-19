<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hi_sajbdp.css';
import '../../css/x/xk7ze-bqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":18,"height":16};
const content = `<path class="hi_sajbdp"/><path class="xk7ze-bqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:images" /></template>

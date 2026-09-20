<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exvj5hvyn.css';
import '../../css/s/sdgx1tzay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="exvj5hvyn"/><path class="sdgx1tzay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:audiodeck" /></template>

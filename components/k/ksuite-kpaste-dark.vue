<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tgnha726h.css';
import '../../css/z/zhef83wqk.css';
import '../../css/z/zuvme35ny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tgnha726h"/><path class="zhef83wqk"/><path class="zuvme35ny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ksuite-kpaste-dark" /></template>

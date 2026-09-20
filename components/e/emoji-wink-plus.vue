<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5eph-bdq.css';
import '../../css/q/qr4wsabqv.css';
import '../../css/g/ga3lzib3e.css';
import '../../css/n/njhb20v1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j5eph-bdq"/><path class="qr4wsabqv"/><path class="ga3lzib3e"/><path clip-rule="evenodd" class="njhb20v1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:emoji-wink-plus" /></template>

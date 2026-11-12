<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hm1o5ccoz.css';
import '../../css/o/obkkoglrp.css';
import '../../css/p/p34lxkxwh.css';
import '../../css/i/i-gsmlpun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hm1o5ccoz"/><path class="obkkoglrp"/><path class="p34lxkxwh"/><path class="i-gsmlpun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ksuite-kdrive" /></template>

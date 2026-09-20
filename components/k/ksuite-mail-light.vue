<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7agjebmg.css';
import '../../css/q/qr18a0v8s.css';
import '../../css/d/d7fm7dbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q7agjebmg"/><path class="qr18a0v8s"/><path class="d7fm7dbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ksuite-mail-light" /></template>

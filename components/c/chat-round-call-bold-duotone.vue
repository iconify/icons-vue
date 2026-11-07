<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pip5km_vy.css';
import '../../css/q/qnmkjnbmb.css';
import '../../css/y/yd0a0cc6y.css';
import '../../css/l/leb1eob0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pip5km_vy"/><path clip-rule="evenodd" class="qnmkjnbmb"/><path clip-rule="evenodd" class="yd0a0cc6y"/><path class="leb1eob0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-round-call-bold-duotone" /></template>

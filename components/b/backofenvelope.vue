<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6jby-byc.css';
import '../../css/m/m32igq_in.css';
import '../../css/k/kf81dz8xu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i6jby-byc"/><path class="m32igq_in"/><path class="kf81dz8xu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:backofenvelope" /></template>

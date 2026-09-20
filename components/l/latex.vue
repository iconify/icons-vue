<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5wnjibna.css';
import '../../css/e/emjfvk0xz.css';
import '../../css/e/e9665qbwc.css';
import '../../css/x/x21x2pqay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q5wnjibna"/><path class="emjfvk0xz"/><path class="e9665qbwc"/><path class="x21x2pqay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:latex" /></template>

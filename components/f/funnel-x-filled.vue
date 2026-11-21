<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xi6y65ble.css';
import '../../css/j/j2lg5bcnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xi6y65ble"/><path class="j2lg5bcnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:funnel-x-filled" /></template>

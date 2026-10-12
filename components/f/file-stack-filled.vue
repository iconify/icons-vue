<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udjwmmbyu.css';
import '../../css/i/ily3ncazb.css';
import '../../css/m/mjwibbccu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udjwmmbyu"/><path class="ily3ncazb"/><path class="mjwibbccu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:file-stack-filled" /></template>

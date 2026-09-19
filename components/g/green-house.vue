<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqtpnnt2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqtpnnt2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:green-house" /></template>

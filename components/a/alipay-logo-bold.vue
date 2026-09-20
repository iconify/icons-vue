<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hz71yshvb.css';
import '../../css/k/k9--tbbhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hz71yshvb"/><path class="k9--tbbhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:alipay-logo-bold" /></template>

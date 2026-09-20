<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mt_4_ts2l.css';
import '../../css/o/oak52ubup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mt_4_ts2l"/><path class="oak52ubup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:email-mailbox-close" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p30qmac3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="p30qmac3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-alert-alarm-bell-off-disable-silent-notification-off-silence-alarm-bell-alert" /></template>

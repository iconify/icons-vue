<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwv3g5b-i.css';
import '../../css/x/xftpn6bca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rwv3g5b-i"/><path class="xftpn6bca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bigcapital" /></template>

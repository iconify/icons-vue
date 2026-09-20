<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trlnbcbjf.css';
import '../../css/w/wie2-nbpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="trlnbcbjf"/><path class="wie2-nbpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lunasea" /></template>

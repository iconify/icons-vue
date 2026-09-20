<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mid6vpnoc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mid6vpnoc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:chimney-filled" /></template>

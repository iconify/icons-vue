<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifxkkbcpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ifxkkbcpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:door-open-solid" /></template>

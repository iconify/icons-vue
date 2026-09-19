<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpnp057-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vpnp057-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:audacity" /></template>

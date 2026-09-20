<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2ctyqcpf.css';
import '../../css/t/trdxx3lxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b2ctyqcpf"/><path class="trdxx3lxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:frappe-crm" /></template>

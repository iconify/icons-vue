<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4d9-5bmv.css';
import '../../css/m/mad6u8jan.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p4d9-5bmv"/><path class="mad6u8jan"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:american-airlines-dark" /></template>

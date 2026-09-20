<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snnycugqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="snnycugqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:globe-filled" /></template>

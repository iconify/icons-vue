<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqf5vsmca.css';
import '../../css/d/ddaib_rgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oqf5vsmca"/><path class="ddaib_rgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:cloud-download" /></template>

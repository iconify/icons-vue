<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6qpn1xxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y6qpn1xxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:apache-hadoop" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwpn5jbfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwpn5jbfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:general-electric" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5wl3gvdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x5wl3gvdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:hot-net" /></template>

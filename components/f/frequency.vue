<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrf6iq1zk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jrf6iq1zk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:frequency" /></template>

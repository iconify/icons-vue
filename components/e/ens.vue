<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sop0dvbuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sop0dvbuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:ens" /></template>

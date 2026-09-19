<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ig5g98dmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ig5g98dmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:blister-pills-oval-x4" /></template>

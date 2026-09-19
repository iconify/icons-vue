<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gv5dp4p7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gv5dp4p7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:aqara-u100" /></template>

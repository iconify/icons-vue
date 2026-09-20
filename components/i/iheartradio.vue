<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gsfxo5bvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gsfxo5bvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:iheartradio" /></template>

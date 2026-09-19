<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frn1yib1k.css';
import '../../css/y/y47svzb0n.css';
import '../../css/h/h6c82bcwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="frn1yib1k"/><path class="y47svzb0n"/><path class="h6c82bcwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-settings-strong" /></template>

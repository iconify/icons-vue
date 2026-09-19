<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afvvtb2te.css';
import '../../css/l/lxung_xah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="afvvtb2te"/><path class="lxung_xah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-grid-view" /></template>

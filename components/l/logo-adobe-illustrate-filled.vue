<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4xr0yhpn.css';
import '../../css/w/wxkzprrkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4xr0yhpn"/><path class="wxkzprrkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:logo-adobe-illustrate-filled" /></template>

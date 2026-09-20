<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yz-efebcs.css';
import '../../css/m/mlbjv-b-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yz-efebcs"/><path class="mlbjv-b-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:explicit-content-duotone" /></template>

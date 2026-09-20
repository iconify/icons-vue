<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wl0ks-bnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wl0ks-bnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:file-contract" /></template>

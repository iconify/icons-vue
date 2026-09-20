<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/po_imbccw.css';
import '../../css/v/vla37tbfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="po_imbccw"/><path class="vla37tbfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:exclamation-circle-duotone" /></template>

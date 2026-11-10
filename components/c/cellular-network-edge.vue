<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3y9rzbfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u3y9rzbfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:cellular-network-edge" /></template>

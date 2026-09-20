<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9m2ddbuh.css';
import '../../css/p/pfsh8mdfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h9m2ddbuh"/><path class="pfsh8mdfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:alpha-wallet" /></template>

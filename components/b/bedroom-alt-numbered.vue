<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gix6z2bdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gix6z2bdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bedroom-alt-numbered" /></template>

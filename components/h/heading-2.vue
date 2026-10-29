<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqubvn-gw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uqubvn-gw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:heading-2" /></template>

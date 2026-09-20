<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fe-e3cc2p.css';
import '../../css/y/y8v76ebvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fe-e3cc2p"/><path class="y8v76ebvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:html3-alt" /></template>

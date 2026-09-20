<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbpv6pbxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gbpv6pbxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:capcut" /></template>

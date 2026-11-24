<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b717o-bps.css';
import '../../css/g/gigg_sbik.css';
import '../../css/s/supxy0b7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b717o-bps"/><path class="gigg_sbik"/><path class="supxy0b7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:house-arrow-left-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgpam7bdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgpam7bdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:mail-arrow-right" /></template>

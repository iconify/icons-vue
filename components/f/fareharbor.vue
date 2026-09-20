<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plyr68b_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="plyr68b_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:fareharbor" /></template>

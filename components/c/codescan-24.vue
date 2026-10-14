<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ij8caccud.css';
import '../../css/p/p05vswb1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ij8caccud"/><path class="p05vswb1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:codescan-24" /></template>

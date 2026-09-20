<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmryhwkxv.css';
import '../../css/b/b1c8iacsb.css';
import '../../css/n/nxqynyklf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tmryhwkxv"/><path class="b1c8iacsb"/><path class="nxqynyklf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:illustrator" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yt6x9_b7p.css';
import '../../css/i/iu35e1xme.css';
import '../../css/w/wa-7pugao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yt6x9_b7p"/><circle class="iu35e1xme"/><path class="wa-7pugao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:exclamation-octagon" /></template>

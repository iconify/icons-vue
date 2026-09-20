<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4qc7h.css';
import '../../css/i/iw1iew.css';
import '../../css/w/w52vln.css';
import '../../css/f/fill-to-0.css';
import '../../css/s/so-from-60.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i4qc7h iw1iew"/><path class="iw1iew w52vln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:confirm-circle-twotone" /></template>

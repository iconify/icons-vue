<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pj8wlmhgm.css';
import '../../css/x/xpk_g7bnh.css';
import '../../css/w/wgy-zbb8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pj8wlmhgm"/><path class="xpk_g7bnh"/><path class="wgy-zbb8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:dataprep" /></template>

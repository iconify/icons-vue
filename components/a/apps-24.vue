<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hm2t-hb9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hm2t-hb9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:apps-24" /></template>

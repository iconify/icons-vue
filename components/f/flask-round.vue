<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hpbmm38ti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hpbmm38ti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flask-round" /></template>

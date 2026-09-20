<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hb_qf6ies.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hb_qf6ies"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:lamp2-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8o_qbc7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m8o_qbc7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:adobe-dreamweaver" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzg34bctw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mzg34bctw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:dots-square" /></template>

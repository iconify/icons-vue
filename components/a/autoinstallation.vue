<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lell8f7di.css';
import '../../css/t/tvlrzedqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lell8f7di"/><path class="tvlrzedqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:autoinstallation" /></template>

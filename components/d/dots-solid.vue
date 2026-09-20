<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4nn-bctw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4nn-bctw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:dots-solid" /></template>

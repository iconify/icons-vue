<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqq2j3bkt.css';
import '../../css/e/esv5bmbuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aqq2j3bkt"/><path class="esv5bmbuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:coffee-filled" /></template>

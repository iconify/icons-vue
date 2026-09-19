<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmsn-19xf.css';
import '../../css/b/beajqbc6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmsn-19xf"/><path class="beajqbc6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:finger-swipe-right" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhxnkh_mo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qhxnkh_mo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:chevron-left-square-filled" /></template>

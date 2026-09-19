<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igt4slb-u.css';
import '../../css/r/rfo4zzbxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="igt4slb-u"/><path class="rfo4zzbxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-out-down-square-half-filled" /></template>

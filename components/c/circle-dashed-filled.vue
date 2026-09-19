<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0x597vfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0x597vfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:circle-dashed-filled" /></template>

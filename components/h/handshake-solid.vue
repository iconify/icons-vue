<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/of_bt5blv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="of_bt5blv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:handshake-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ky5j3dbtq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ky5j3dbtq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:account-pin-box-fill" /></template>

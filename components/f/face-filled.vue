<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qilianfni.css';
import '../../css/s/ssuhewbiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qilianfni"/><path class="ssuhewbiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:face-filled" /></template>

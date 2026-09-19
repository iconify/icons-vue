<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3k9861yd.css';
import '../../css/s/sizcdbmji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v3k9861yd"/><path class="sizcdbmji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bell-check" /></template>

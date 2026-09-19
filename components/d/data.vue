<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqsnjmbdm.css';
import '../../css/k/kykp8gb1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mqsnjmbdm"/><path class="kykp8gb1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:data" /></template>

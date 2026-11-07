<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kflf7crkg.css';
import '../../css/a/aam5d_bgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kflf7crkg"/><path clip-rule="evenodd" class="aam5d_bgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:call-medicine-rounded-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmr_aobwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qmr_aobwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:desk-02" /></template>

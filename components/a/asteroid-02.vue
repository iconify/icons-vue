<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qeabq0brs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qeabq0brs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:asteroid-02" /></template>

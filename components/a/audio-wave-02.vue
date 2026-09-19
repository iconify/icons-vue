<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzkqj_b3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zzkqj_b3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:audio-wave-02" /></template>

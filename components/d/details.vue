<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qk_hy4r_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qk_hy4r_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:details" /></template>

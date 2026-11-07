<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngq_w4btn.css';
import '../../css/h/htgnsl4vu.css';
import '../../css/v/vte5evnzt.css';
import '../../css/f/f9hzkm85j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ngq_w4btn"/><path class="htgnsl4vu"/><path class="vte5evnzt"/><path class="f9hzkm85j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:box-bold" /></template>

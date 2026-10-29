<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h364t7brs.css';
import '../../css/i/i2z-fkbgx.css';
import '../../css/v/vbn0d_b5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h364t7brs wm-shadow"/><path class="i2z-fkbgx wm-k"/><path class="vbn0d_b5k wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-pastel:chevron-up" /></template>

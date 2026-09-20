<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-rpmy.css';
import '../../css/y/yi8b0f.css';
import '../../css/f/fill-to-0.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-from-30.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-rpmy"/><path class="yi8b0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:heart-twotone-half" /></template>

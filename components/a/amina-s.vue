<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bn_3_8bay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bn_3_8bay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:amina-s" /></template>

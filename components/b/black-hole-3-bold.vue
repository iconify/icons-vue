<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzg_r58ne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kzg_r58ne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:black-hole-3-bold" /></template>

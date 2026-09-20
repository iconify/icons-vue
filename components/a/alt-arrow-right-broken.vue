<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cz-yv_bhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cz-yv_bhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:alt-arrow-right-broken" /></template>

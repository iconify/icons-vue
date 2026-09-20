<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wq0dy3n_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wq0dy3n_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:bank-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aoo-m9bse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aoo-m9bse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:configuration-safety" /></template>

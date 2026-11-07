<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcwkts_fc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bcwkts_fc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:body-linear" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eog_v_cug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eog_v_cug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:harmonyos" /></template>

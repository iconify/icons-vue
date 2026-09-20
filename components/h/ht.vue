<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_t11abfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_t11abfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ht" /></template>

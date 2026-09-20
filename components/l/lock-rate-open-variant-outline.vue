<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bo8123eqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bo8123eqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:lock-rate-open-variant-outline" /></template>

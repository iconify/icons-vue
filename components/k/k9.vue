<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qs0_gzboc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qs0_gzboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:k9" /></template>

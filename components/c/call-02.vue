<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v73h0031l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v73h0031l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:call-02" /></template>

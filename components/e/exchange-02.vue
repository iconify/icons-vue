<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgcy-jbmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rgcy-jbmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:exchange-02" /></template>

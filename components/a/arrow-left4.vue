<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k62k3eb6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k62k3eb6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-left4" /></template>

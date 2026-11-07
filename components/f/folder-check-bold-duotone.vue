<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2nrf10bf.css';
import '../../css/j/jyzx5uolb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q2nrf10bf"/><path class="jyzx5uolb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-check-bold-duotone" /></template>

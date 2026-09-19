<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zma5sabei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zma5sabei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ceiling-fugato-three-alt" /></template>

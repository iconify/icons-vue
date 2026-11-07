<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_en--b-n.css';
import '../../css/w/wru8zmbec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_en--b-n"/><path clip-rule="evenodd" class="wru8zmbec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:home-smile-angle-outline" /></template>

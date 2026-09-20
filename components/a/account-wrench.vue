<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tip5qcczg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tip5qcczg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:account-wrench" /></template>

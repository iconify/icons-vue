<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efmcpmb6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="efmcpmb6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:ideogram-chinese-japanese-korean" /></template>

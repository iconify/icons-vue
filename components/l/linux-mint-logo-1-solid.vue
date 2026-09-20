<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5pzh1ksk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e5pzh1ksk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:linux-mint-logo-1-solid" /></template>

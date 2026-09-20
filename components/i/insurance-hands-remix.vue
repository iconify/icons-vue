<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkh-m2dpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pkh-m2dpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:insurance-hands-remix" /></template>

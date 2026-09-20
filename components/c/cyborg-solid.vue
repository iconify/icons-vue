<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xz2u3n6qt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xz2u3n6qt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:cyborg-solid" /></template>

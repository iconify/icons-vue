<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmf4z0u-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xmf4z0u-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:git-return-sharp" /></template>

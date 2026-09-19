<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/urr2ffbyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="urr2ffbyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:donate-blood-filled" /></template>

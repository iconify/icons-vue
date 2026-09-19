<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gyowgpbei.css';
import '../../css/n/nwz75bygh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gyowgpbei"/><path class="nwz75bygh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-building-house" /></template>

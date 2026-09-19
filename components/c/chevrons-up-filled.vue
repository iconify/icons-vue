<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1qupzz3x.css';
import '../../css/t/tc13xdone.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v1qupzz3x"/><path class="tc13xdone"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:chevrons-up-filled" /></template>

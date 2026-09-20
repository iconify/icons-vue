<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxck67bbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xxck67bbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bulb-filled" /></template>

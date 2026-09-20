<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dn-sgwbhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dn-sgwbhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:barrier-block-filled" /></template>

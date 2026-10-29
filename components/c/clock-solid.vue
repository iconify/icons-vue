<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jk_cstb7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jk_cstb7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:clock-solid" /></template>

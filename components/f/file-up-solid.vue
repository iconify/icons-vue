<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bak1p_6df.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bak1p_6df"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:file-up-solid" /></template>

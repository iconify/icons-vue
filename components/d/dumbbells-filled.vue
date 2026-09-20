<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ai6f-hbxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ai6f-hbxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:dumbbells-filled" /></template>

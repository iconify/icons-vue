<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g16a0vbxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g16a0vbxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:air-balloon-filled" /></template>

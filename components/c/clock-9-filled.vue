<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cz90c6mjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cz90c6mjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:clock-9-filled" /></template>

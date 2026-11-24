<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbodqlbep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xbodqlbep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bone-filled" /></template>

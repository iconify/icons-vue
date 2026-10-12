<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gctu84qqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gctu84qqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:currency-filled" /></template>

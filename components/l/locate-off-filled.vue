<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edv3dcb8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="edv3dcb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:locate-off-filled" /></template>

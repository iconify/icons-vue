<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xk2_ziukt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xk2_ziukt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:anchor-filled" /></template>

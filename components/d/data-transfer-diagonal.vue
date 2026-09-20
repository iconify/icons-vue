<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5cl7x5rb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k5cl7x5rb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:data-transfer-diagonal" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5nts0blq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k5nts0blq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:lock-2-fill" /></template>

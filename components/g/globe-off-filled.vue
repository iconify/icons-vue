<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kslho1p0c.css';
import '../../css/l/lizimdblx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kslho1p0c"/><path class="lizimdblx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:globe-off-filled" /></template>

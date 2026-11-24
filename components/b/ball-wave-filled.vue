<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v72yvk6dr.css';
import '../../css/e/e2m9rbc6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v72yvk6dr"/><path clip-rule="evenodd" class="e2m9rbc6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:ball-wave-filled" /></template>

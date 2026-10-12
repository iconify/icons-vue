<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grda5wb_p.css';
import '../../css/e/e_r9uibzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="grda5wb_p"/><path class="e_r9uibzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:database-check-filled" /></template>

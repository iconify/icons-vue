<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_r9uibzg.css';
import '../../css/c/cdu9hfbeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_r9uibzg"/><path clip-rule="evenodd" class="cdu9hfbeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bot-check-filled" /></template>

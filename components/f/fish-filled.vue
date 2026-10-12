<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqgpg9bzx.css';
import '../../css/a/atb87lbap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqgpg9bzx"/><path clip-rule="evenodd" class="atb87lbap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:fish-filled" /></template>

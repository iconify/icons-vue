<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qn4bc_bdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qn4bc_bdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:indent-solid" /></template>

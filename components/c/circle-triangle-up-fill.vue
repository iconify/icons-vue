<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_rfhtbne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v_rfhtbne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:circle-triangle-up-fill" /></template>

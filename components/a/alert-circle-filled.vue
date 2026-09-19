<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smqjcg2tk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smqjcg2tk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:alert-circle-filled" /></template>

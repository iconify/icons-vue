<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msn1kjbyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="msn1kjbyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:clipboard-check-filled" /></template>

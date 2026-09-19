<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnnsfxb0b.css';
import '../../css/t/t4ibq1bzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pnnsfxb0b"/><path class="t4ibq1bzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:document-currency-euro-solid" /></template>

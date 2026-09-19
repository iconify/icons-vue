<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkkm6ncsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pkkm6ncsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:document-currency-yen-solid" /></template>

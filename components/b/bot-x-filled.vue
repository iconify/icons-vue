<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tp17bzlwb.css';
import '../../css/m/m9m_5-b5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tp17bzlwb"/><path clip-rule="evenodd" class="m9m_5-b5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bot-x-filled" /></template>

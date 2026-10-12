<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pl8_zgbvz.css';
import '../../css/o/o5nyr_biv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pl8_zgbvz"/><path class="o5nyr_biv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:hand-platter-filled" /></template>

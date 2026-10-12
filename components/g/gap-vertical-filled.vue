<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbpdsdbdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbpdsdbdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:gap-vertical-filled" /></template>

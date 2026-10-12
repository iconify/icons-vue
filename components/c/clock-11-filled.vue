<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gii8jmkiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gii8jmkiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:clock-11-filled" /></template>

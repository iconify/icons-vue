<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5ej4pbho.css';
import '../../css/c/c6etmkbzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d5ej4pbho"/><path class="c6etmkbzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:face-mask-filled" /></template>

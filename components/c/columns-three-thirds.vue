<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/paejl3bra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="paejl3bra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:columns-three-thirds" /></template>

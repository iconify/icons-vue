<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wk88qlbwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wk88qlbwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:face-angry-filled" /></template>

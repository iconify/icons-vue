<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zoqiw4b5c.css';
import '../../css/l/lg9rrm_lz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zoqiw4b5c"/><path class="lg9rrm_lz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:lasso-select-filled" /></template>

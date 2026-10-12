<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ld-ldz2zs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ld-ldz2zs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:fast-forward-filled" /></template>

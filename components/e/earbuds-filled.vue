<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eeyns4pbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eeyns4pbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:earbuds-filled" /></template>

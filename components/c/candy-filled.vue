<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jt9ao2b2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jt9ao2b2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:candy-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ali15_c0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ali15_c0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:face-expressionless-filled" /></template>

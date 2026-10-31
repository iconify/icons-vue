<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zj60v6byq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zj60v6byq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:circle-letter-y-filled" /></template>

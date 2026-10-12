<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebvylcb7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ebvylcb7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:balloon-filled" /></template>

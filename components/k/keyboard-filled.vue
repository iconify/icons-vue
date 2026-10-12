<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shrbis3_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="shrbis3_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:keyboard-filled" /></template>

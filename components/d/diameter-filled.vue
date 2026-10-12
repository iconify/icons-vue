<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hce5xfkpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hce5xfkpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:diameter-filled" /></template>

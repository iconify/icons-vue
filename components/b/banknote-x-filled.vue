<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3qof8bab.css';
import '../../css/t/tbf2vectn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c3qof8bab"/><path clip-rule="evenodd" class="tbf2vectn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:banknote-x-filled" /></template>

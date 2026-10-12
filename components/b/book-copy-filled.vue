<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2nr3_bdv.css';
import '../../css/t/tkgm1jb2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t2nr3_bdv"/><path clip-rule="evenodd" class="tkgm1jb2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:book-copy-filled" /></template>

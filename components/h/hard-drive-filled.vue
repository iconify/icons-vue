<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adkx26buk.css';
import '../../css/e/ex3oebbia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="adkx26buk"/><path class="ex3oebbia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:hard-drive-filled" /></template>

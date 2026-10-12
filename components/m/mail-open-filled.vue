<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8sn5607z.css';
import '../../css/p/puqsb9b7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a8sn5607z"/><path class="puqsb9b7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:mail-open-filled" /></template>

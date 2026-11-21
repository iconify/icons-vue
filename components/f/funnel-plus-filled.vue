<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx7s2abfj.css';
import '../../css/e/exoou0b0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lx7s2abfj"/><path class="exoou0b0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:funnel-plus-filled" /></template>

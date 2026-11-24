<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhdi6ccum.css';
import '../../css/a/ab-wz6bnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhdi6ccum"/><path class="ab-wz6bnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:database-arrow-up-filled" /></template>

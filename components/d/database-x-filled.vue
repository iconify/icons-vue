<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eak-paccj.css';
import '../../css/h/hiszw8brf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eak-paccj"/><path class="hiszw8brf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:database-x-filled" /></template>

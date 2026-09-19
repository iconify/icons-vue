<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9-ohxbke.css';
import '../../css/e/ehyq6ihjz.css';
import '../../css/t/t3va_bxxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="x9-ohxbke"/><circle class="ehyq6ihjz"/><path class="t3va_bxxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:cart-sharp" /></template>

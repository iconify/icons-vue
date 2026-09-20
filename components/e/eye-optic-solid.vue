<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/litncn_oq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="litncn_oq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:eye-optic-solid" /></template>

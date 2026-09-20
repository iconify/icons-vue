<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s271kzbcl.css';
import '../../css/c/cw8eslg_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s271kzbcl"/><path class="cw8eslg_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:blackberry" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kc75hcczw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kc75hcczw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:church-round" /></template>

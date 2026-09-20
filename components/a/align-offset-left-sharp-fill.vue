<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdl7h5bjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pdl7h5bjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-offset-left-sharp-fill" /></template>

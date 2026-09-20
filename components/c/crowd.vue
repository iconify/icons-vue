<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mnlh_2gfq.css';
import '../../css/u/uqv04wb6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mnlh_2gfq"/><path class="uqv04wb6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:crowd" /></template>

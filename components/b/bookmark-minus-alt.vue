<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mf19ixb5n.css';
import '../../css/t/t_qou-ite.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mf19ixb5n"/><path class="t_qou-ite"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bookmark-minus-alt" /></template>

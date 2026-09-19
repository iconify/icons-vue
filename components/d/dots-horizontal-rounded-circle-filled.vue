<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-4bhxunp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-4bhxunp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dots-horizontal-rounded-circle-filled" /></template>

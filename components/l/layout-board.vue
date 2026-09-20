<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbel9vblw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbel9vblw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:layout-board" /></template>

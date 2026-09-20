<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxae0_noe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kxae0_noe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:float-center" /></template>

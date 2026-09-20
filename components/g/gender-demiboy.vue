<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zuim5fb4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zuim5fb4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:gender-demiboy" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tkdmrs04o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tkdmrs04o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:community" /></template>

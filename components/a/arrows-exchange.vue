<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gevhiyxvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gevhiyxvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrows-exchange" /></template>

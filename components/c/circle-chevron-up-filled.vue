<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxawrmb7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xxawrmb7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-chevron-up-filled" /></template>

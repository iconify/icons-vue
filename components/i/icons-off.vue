<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsn7bex_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xsn7bex_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:icons-off" /></template>

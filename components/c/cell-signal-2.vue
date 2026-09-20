<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etx7hfm9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="etx7hfm9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:cell-signal-2" /></template>

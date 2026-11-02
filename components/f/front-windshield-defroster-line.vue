<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_p2-wb2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_p2-wb2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:front-windshield-defroster-line" /></template>

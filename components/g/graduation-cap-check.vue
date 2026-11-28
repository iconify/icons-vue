<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ep3yudvpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ep3yudvpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:graduation-cap-check" /></template>

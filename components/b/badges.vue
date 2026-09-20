<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/es3nb9bbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="es3nb9bbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:badges" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obfv3yb1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="obfv3yb1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:filter-minus" /></template>

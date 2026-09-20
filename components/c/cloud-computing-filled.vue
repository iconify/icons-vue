<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_ma10age.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o_ma10age"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:cloud-computing-filled" /></template>

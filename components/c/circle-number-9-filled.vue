<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bd81ub8rn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bd81ub8rn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-number-9-filled" /></template>

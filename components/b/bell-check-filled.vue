<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_9t_z5eb.css';
import '../../css/k/k6i9o7bvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_9t_z5eb"/><path class="k6i9o7bvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bell-check-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkj7k3nbl.css';
import '../../css/z/z0lqnqbjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bkj7k3nbl"/><path clip-rule="evenodd" class="z0lqnqbjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:import-bold-duotone" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j25q1q_nx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j25q1q_nx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:caution-fence" /></template>

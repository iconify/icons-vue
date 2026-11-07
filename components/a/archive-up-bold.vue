<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujz70yoss.css';
import '../../css/s/s6dl6st5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ujz70yoss"/><path class="s6dl6st5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:archive-up-bold" /></template>

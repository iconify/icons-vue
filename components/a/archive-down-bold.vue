<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wm-fdvb-j.css';
import '../../css/s/s6dl6st5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-fdvb-j"/><path class="s6dl6st5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:archive-down-bold" /></template>
